<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eprcz8brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eprcz8brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-37-small" {...props}></Icon>
