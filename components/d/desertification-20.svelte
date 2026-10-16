<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf4d2jblq.css';
import '../../css/t/tmmpscb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gf4d2jblq"/><path class="tmmpscb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desertification-20" {...props}></Icon>
