<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auvszdnuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="auvszdnuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rolled-curb" {...props}></Icon>
