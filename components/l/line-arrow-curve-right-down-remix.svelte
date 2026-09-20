<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np7lh-0vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="np7lh-0vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-curve-right-down-remix" {...props}></Icon>
