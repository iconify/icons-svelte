<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1swbq5zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z1swbq5zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:melpa" {...props}></Icon>
