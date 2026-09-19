<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnpn7ob-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qnpn7ob-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:db2-data-sharing-group" {...props}></Icon>
