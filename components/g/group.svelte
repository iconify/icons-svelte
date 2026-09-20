<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkowd7_ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jkowd7_ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:group" {...props}></Icon>
