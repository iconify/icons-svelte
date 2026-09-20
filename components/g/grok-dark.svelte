<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_dwuhmht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f_dwuhmht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:grok-dark" {...props}></Icon>
