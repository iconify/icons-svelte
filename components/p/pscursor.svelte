<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scb29lb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="scb29lb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pscursor" {...props}></Icon>
