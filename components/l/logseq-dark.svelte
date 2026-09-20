<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag-domk8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ag-domk8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:logseq-dark" {...props}></Icon>
