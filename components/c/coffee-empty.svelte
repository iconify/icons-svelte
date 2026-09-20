<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxbrcacrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxbrcacrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:coffee-empty" {...props}></Icon>
