<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h672n2bmz.css';
import '../../css/y/ysryh6dqp.css';
import '../../css/a/ax9-5db1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h672n2bmz"/><path class="ysryh6dqp"/><path class="ax9-5db1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:elderly-20-bold" {...props}></Icon>
