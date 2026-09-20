<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmy8lab0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bmy8lab0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:horseshoe-with-stake" {...props}></Icon>
