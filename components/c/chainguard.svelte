<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx2j0nbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx2j0nbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chainguard" {...props}></Icon>
