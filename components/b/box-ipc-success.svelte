<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm_2zebzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hm_2zebzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:box-ipc-success" {...props}></Icon>
