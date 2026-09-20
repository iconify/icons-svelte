<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgvl3po6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jgvl3po6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cyborg-remix" {...props}></Icon>
