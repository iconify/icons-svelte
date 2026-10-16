<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-7qfebjm.css';
import '../../css/f/ff0-2zv2c.css';
import '../../css/e/egip2ibxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t-7qfebjm"/><path class="ff0-2zv2c"/><path class="egip2ibxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-holder-20" {...props}></Icon>
