<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzc8m079p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hzc8m079p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:maximize-fill-12" {...props}></Icon>
