<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otcc7pvhw.css';
import '../../css/p/p6vzlj6qq.css';
import '../../css/s/s7q2gertg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="otcc7pvhw"/><path class="p6vzlj6qq"/><path class="s7q2gertg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fingerprint-48" {...props}></Icon>
