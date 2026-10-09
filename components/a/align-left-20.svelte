<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo6miub8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vo6miub8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-left-20" {...props}></Icon>
