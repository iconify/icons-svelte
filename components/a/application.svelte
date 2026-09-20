<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcfear6ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dcfear6ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:application" {...props}></Icon>
