<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htyf4ib6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="htyf4ib6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:question-face" {...props}></Icon>
