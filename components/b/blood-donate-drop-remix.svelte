<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nub9o5gbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nub9o5gbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:blood-donate-drop-remix" {...props}></Icon>
