<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5bqxjb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5bqxjb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevron-left-square" {...props}></Icon>
