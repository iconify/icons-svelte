<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j068h3bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j068h3bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:layout-plus" {...props}></Icon>
