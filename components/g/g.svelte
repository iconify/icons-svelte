<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txpzpubtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":562,"height":881};
const content = `<path class="txpzpubtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:g" {...props}></Icon>
