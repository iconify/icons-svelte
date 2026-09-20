<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3oizr6zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v3oizr6zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-upright-full" {...props}></Icon>
