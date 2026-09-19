<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzze97bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="tzze97bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bell-slash" {...props}></Icon>
