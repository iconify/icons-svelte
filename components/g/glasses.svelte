<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx5e0zz-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hx5e0zz-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:glasses" {...props}></Icon>
