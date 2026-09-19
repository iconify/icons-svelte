<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3d1-5b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3d1-5b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:list-remove" {...props}></Icon>
