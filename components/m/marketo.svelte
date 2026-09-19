<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngo9cq6cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ngo9cq6cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:marketo" {...props}></Icon>
