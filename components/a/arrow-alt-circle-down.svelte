<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k40dcvkuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k40dcvkuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:arrow-alt-circle-down" {...props}></Icon>
