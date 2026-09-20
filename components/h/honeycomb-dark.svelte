<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrnfgtxba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":164,"height":48};
const content = `<path class="zrnfgtxba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:honeycomb-dark" {...props}></Icon>
