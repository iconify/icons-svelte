<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmlg3s19r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="pmlg3s19r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bold" {...props}></Icon>
