<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_5d7pbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_5d7pbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-7-line" {...props}></Icon>
