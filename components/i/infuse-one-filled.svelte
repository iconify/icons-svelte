<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u78s60hcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u78s60hcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:infuse-one-filled" {...props}></Icon>
