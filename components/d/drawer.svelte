<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnhtjtfld.css';
import '../../css/o/ovp4s65sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nnhtjtfld"/><path class="ovp4s65sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:drawer" {...props}></Icon>
