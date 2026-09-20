<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln9646oal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ln9646oal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pinterest-outline" {...props}></Icon>
