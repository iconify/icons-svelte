<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cay9onbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cay9onbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-filing-outline" {...props}></Icon>
