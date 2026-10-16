<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8314acox.css';
import '../../css/f/falraebon.css';
import '../../css/l/lhy98hwgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o8314acox"/><path class="falraebon"/><path class="lhy98hwgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cassette-48-bold" {...props}></Icon>
