<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlt7b8b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="dlt7b8b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layout-window-2" {...props}></Icon>
