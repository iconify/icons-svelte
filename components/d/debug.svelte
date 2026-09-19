<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia8cb7bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="ia8cb7bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:debug" {...props}></Icon>
