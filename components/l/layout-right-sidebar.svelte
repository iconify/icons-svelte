<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgk3cb3nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hgk3cb3nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:layout-right-sidebar" {...props}></Icon>
