<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybwg6ub2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybwg6ub2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:namebase" {...props}></Icon>
