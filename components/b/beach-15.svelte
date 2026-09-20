<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfi9zl2px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gfi9zl2px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:beach-15" {...props}></Icon>
