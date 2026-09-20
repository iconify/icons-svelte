<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcuwd4bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qcuwd4bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crates-under-roof" {...props}></Icon>
