<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kerc9_bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kerc9_bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-running" {...props}></Icon>
