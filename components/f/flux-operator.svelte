<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9gh3cbby.css';
import '../../css/g/gljjdb6ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9gh3cbby"/><path class="gljjdb6ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flux-operator" {...props}></Icon>
