<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3il3ycro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e3il3ycro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:blank-calendar-solid" {...props}></Icon>
