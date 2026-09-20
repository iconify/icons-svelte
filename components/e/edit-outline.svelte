<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awf25-t-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="awf25-t-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:edit-outline" {...props}></Icon>
