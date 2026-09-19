<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywz-nyv8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="ywz-nyv8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:account-o" {...props}></Icon>
