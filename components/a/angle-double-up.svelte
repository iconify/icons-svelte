<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3n-6q79x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3n-6q79x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:angle-double-up" {...props}></Icon>
