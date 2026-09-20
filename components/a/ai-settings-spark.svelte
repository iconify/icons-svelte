<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzvzc6bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zzvzc6bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-settings-spark" {...props}></Icon>
