<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr5utj3pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr5utj3pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-sublime-text" {...props}></Icon>
