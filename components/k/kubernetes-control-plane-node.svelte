<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eje_24crj.css';
import '../../css/e/e35vx9b8n.css';
import '../../css/x/x8r3bo3uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eje_24crj"/><path class="e35vx9b8n"/><path class="x8r3bo3uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:kubernetes-control-plane-node" {...props}></Icon>
