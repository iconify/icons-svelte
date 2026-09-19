<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naj-5-b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="naj-5-b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:dots-circle-horizontal" {...props}></Icon>
