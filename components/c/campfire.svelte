<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emxjnlb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="emxjnlb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campfire" {...props}></Icon>
