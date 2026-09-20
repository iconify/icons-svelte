<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7k35bb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g7k35bb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dope-security-dark" {...props}></Icon>
