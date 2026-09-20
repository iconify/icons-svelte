<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zppixabqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zppixabqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pocket-casts" {...props}></Icon>
