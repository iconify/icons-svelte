<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3hmnhbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3hmnhbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-circle-right" {...props}></Icon>
