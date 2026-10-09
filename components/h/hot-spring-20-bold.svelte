<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8mq92bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f8mq92bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-spring-20-bold" {...props}></Icon>
