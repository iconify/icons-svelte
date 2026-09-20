<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo3c0ibak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo3c0ibak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:git" {...props}></Icon>
