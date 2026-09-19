<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iet1eb9kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iet1eb9kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:nginx" {...props}></Icon>
