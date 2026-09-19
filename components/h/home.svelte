<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsrj86a-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="lsrj86a-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:home" {...props}></Icon>
