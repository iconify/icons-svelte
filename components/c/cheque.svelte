<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqyl0nvla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqyl0nvla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cheque" {...props}></Icon>
