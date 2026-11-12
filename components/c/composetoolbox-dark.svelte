<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yor-hx2rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yor-hx2rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:composetoolbox-dark" {...props}></Icon>
