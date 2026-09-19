<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8pvc7bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="h8pvc7bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:fire-flame-curved" {...props}></Icon>
