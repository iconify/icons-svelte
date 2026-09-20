<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exxlsgbrx.css';
import '../../css/s/senys3bzh.css';
import '../../css/b/by3-pxb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exxlsgbrx"/><path class="senys3bzh"/><path class="by3-pxb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-data-conversion-documents-2-bold" {...props}></Icon>
