<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8wrg7o9z.css';
import '../../css/w/wgxunzb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o8wrg7o9z"/><ellipse class="wgxunzb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:mobile" {...props}></Icon>
