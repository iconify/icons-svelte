<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcuf-ab3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="tcuf-ab3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cloud-arrow-up" {...props}></Icon>
