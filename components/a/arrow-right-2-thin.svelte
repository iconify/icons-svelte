<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7tbqzbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7tbqzbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-2-thin" {...props}></Icon>
