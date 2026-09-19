<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaneu_gmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaneu_gmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-line-height" {...props}></Icon>
