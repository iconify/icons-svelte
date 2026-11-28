<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brk9uu4sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brk9uu4sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:crop-solid" {...props}></Icon>
