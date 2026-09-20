<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkl8r-3at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkl8r-3at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:eye-table" {...props}></Icon>
