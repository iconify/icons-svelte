<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfsz5_b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nfsz5_b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:latex" {...props}></Icon>
