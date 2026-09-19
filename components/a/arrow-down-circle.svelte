<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crwfztb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="crwfztb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-circle" {...props}></Icon>
