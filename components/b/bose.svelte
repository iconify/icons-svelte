<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0o-lx78j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0o-lx78j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bose" {...props}></Icon>
