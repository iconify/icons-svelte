<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpf1zacks.css';
import '../../css/n/nqe79lxrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kpf1zacks"/><path class="nqe79lxrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-hospital-building-2" {...props}></Icon>
