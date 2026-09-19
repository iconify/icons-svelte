<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq_qswbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nq_qswbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bottom-panel-close-filled" {...props}></Icon>
