<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq-nchcxv.css';
import '../../css/d/dlp7nstpk.css';
import '../../css/q/qe3jhfb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mq-nchcxv"/><circle class="dlp7nstpk"/><path class="qe3jhfb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:object-storage" {...props}></Icon>
