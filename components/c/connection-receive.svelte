<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpl6w6far.css';
import '../../css/n/n7xm2kttp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gpl6w6far"/><path class="n7xm2kttp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:connection-receive" {...props}></Icon>
