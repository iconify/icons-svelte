<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul7b5x6-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul7b5x6-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:a-frame" {...props}></Icon>
