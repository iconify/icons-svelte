<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-4c2875v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-4c2875v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:allegro" {...props}></Icon>
