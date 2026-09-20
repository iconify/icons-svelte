<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1707cbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1707cbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-up" {...props}></Icon>
