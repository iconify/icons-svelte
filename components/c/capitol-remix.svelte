<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um10u-bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="um10u-bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:capitol-remix" {...props}></Icon>
