<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am4viierx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="am4viierx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cherries-remix" {...props}></Icon>
