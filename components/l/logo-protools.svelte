<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy_cr8baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xy_cr8baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-protools" {...props}></Icon>
