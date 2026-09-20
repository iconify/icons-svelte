<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud1cjwbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ud1cjwbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:endless" {...props}></Icon>
