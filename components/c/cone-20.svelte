<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1c-dgbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q1c-dgbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cone-20" {...props}></Icon>
