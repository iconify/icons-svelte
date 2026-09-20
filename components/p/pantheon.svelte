<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0ojc0izp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0ojc0izp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pantheon" {...props}></Icon>
