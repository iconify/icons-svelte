<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbpckrb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cbpckrb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:opera" {...props}></Icon>
