<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am0o2qbnj.css';
import '../../css/h/hx6oh69ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="am0o2qbnj"/><path class="hx6oh69ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bracket-light" {...props}></Icon>
