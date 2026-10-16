<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2qly6b8v.css';
import '../../css/y/yxx6x7qnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q2qly6b8v"/><path class="yxx6x7qnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-hybrid-20-bold" {...props}></Icon>
