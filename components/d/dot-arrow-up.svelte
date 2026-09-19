<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgqkzk5ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgqkzk5ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:dot-arrow-up" {...props}></Icon>
