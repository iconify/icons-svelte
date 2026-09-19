<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnewt-bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qnewt-bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:koding" {...props}></Icon>
