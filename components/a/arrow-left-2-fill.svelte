<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne96gebqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ne96gebqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-2-fill" {...props}></Icon>
