<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtdx1lb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="gtdx1lb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:creative-commons-nc-eu" {...props}></Icon>
