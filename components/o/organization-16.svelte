<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgy_7bltc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mgy_7bltc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:organization-16" {...props}></Icon>
