<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq-nchcxv.css';
import '../../css/d/dlp7nstpk.css';
import '../../css/m/mukg8ab-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mq-nchcxv"/><circle class="dlp7nstpk"/><path class="mukg8ab-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:object-storage-alt" {...props}></Icon>
