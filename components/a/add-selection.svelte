<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv7k113ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mv7k113ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-selection" {...props}></Icon>
