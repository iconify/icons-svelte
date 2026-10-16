<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezyuvccht.css';
import '../../css/l/lz-h06bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ezyuvccht"/><path class="lz-h06bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-pen-20-bold" {...props}></Icon>
