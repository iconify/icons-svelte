<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trg-1n7hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":287,"height":654};
const content = `<path class="trg-1n7hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:r" {...props}></Icon>
