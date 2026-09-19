<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksv6oqjmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ksv6oqjmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:apple" {...props}></Icon>
