<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eii-1ollo.css';
import '../../css/a/ahciwmy7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="eii-1ollo"/><circle class="ahciwmy7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:gear-stroke-12" {...props}></Icon>
