<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d06n8p3wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="d06n8p3wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:euro-sign" {...props}></Icon>
