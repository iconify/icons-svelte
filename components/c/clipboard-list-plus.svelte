<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkyxbsb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkyxbsb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-list-plus" {...props}></Icon>
