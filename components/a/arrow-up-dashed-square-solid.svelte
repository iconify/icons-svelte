<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufrx95bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ufrx95bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-up-dashed-square-solid" {...props}></Icon>
