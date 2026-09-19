<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz59rmb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zz59rmb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-activitybar-left" {...props}></Icon>
