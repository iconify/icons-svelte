<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnx7xtbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jnx7xtbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:about-filled" {...props}></Icon>
