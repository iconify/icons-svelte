<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5v6nqhga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5v6nqhga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bookmark-plus" {...props}></Icon>
