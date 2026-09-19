<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsd-6j50u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="lsd-6j50u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:diamond" {...props}></Icon>
