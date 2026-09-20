<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2_2ljb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h2_2ljb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:lightbulb" {...props}></Icon>
