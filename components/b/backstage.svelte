<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3kng8m4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3kng8m4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:backstage" {...props}></Icon>
