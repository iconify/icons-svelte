<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py9x-zbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="py9x-zbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dashboard-square-1" {...props}></Icon>
