<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tznma-bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":466,"height":654};
const content = `<path class="tznma-bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:n" {...props}></Icon>
