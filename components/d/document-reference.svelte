<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpe4mlbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tpe4mlbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-reference" {...props}></Icon>
