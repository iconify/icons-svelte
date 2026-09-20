<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw7yodbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zw7yodbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pepper-hot-solid" {...props}></Icon>
