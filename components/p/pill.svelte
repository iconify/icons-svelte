<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ub43w-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="s2ub43w-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:pill" {...props}></Icon>
