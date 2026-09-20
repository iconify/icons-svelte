<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-sa-ubgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="m-sa-ubgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:plug" {...props}></Icon>
