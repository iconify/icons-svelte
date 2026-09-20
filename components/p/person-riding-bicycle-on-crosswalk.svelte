<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gayi84bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gayi84bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-bicycle-on-crosswalk" {...props}></Icon>
