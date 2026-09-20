<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx4c7k3tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tx4c7k3tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-full-check" {...props}></Icon>
