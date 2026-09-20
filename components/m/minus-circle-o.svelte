<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abq_w4bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="abq_w4bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:minus-circle-o" {...props}></Icon>
