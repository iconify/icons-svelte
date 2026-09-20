<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptx2rabpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptx2rabpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pyup" {...props}></Icon>
