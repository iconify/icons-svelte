<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t71jnss5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="t71jnss5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:plus-square" {...props}></Icon>
