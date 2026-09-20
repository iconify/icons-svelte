<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew-ng2h3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew-ng2h3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:medibang-paint" {...props}></Icon>
