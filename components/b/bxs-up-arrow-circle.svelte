<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm4e9_79y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm4e9_79y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-up-arrow-circle" {...props}></Icon>
