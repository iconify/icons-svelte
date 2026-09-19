<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_efqme5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="t_efqme5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:linkedin" {...props}></Icon>
