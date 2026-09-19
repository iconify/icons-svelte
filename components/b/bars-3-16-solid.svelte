<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_59qsblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g_59qsblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3-16-solid" {...props}></Icon>
