<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr22n6bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr22n6bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:parenthesis-right" {...props}></Icon>
