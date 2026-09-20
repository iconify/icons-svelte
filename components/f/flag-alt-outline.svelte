<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwhsll-1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nwhsll-1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:flag-alt-outline" {...props}></Icon>
