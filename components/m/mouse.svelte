<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnc29jbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xnc29jbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:mouse" {...props}></Icon>
