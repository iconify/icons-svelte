<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx51n-rzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lx51n-rzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:pin" {...props}></Icon>
