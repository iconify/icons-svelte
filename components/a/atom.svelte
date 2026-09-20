<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1j74k3mk.css';
import '../../css/g/gknbh0bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<circle class="y1j74k3mk"/><path class="gknbh0bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:atom" {...props}></Icon>
