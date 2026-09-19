<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5n8go3pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="y5n8go3pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:list" {...props}></Icon>
