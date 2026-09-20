<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e29om5blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e29om5blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-using-mounted-binoculars" {...props}></Icon>
