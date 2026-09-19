<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_we1sb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_we1sb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-3-square-thin" {...props}></Icon>
