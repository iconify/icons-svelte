<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq35ehzop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="wq35ehzop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:exit-10" {...props}></Icon>
