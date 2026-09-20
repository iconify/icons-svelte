<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf6u5i5sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sf6u5i5sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bottom-left-outline" {...props}></Icon>
