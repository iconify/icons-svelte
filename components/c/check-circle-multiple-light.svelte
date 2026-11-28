<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_pgq_bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q_pgq_bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:check-circle-multiple-light" {...props}></Icon>
