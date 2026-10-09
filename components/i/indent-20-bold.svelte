<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2z7ddc-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v2z7ddc-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:indent-20-bold" {...props}></Icon>
