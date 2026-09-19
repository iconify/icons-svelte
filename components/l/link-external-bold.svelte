<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccdiidbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccdiidbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:link-external-bold" {...props}></Icon>
