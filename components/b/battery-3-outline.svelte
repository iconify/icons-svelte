<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxmthib0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yxmthib0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:battery-3-outline" {...props}></Icon>
