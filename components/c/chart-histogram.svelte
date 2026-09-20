<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z16kyy6mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z16kyy6mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:chart-histogram" {...props}></Icon>
