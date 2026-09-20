<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v43rpnbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="v43rpnbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-removed" {...props}></Icon>
