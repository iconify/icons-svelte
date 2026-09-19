<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0rk0_b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="j0rk0_b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:animestudio" {...props}></Icon>
