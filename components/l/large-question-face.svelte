<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf32htb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tf32htb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:large-question-face" {...props}></Icon>
