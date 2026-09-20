<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3th3mb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h3th3mb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:hard-drive" {...props}></Icon>
