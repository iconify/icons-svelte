<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8wr0fzqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8wr0fzqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:filter-list-circle" {...props}></Icon>
