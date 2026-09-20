<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts-l0zmzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ts-l0zmzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:book" {...props}></Icon>
