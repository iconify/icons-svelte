<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdr6lg8ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdr6lg8ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-right-1-bold" {...props}></Icon>
