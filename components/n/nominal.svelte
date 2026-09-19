<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8urf5jax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o8urf5jax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:nominal" {...props}></Icon>
