<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urrv_ccnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urrv_ccnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:files" {...props}></Icon>
