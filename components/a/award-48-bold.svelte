<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dibcbtkzz.css';
import '../../css/p/pjb032xjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dibcbtkzz"/><path class="pjb032xjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:award-48-bold" {...props}></Icon>
