<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy7ws3bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gy7ws3bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:code-bracket-20" {...props}></Icon>
