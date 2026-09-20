<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9y-2__bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9y-2__bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mangaupdates" {...props}></Icon>
