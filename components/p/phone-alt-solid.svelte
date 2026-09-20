<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyau3c7zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kyau3c7zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:phone-alt-solid" {...props}></Icon>
