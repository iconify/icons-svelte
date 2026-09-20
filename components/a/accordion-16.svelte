<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weql5sbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="weql5sbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:accordion-16" {...props}></Icon>
