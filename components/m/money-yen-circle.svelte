<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahk5vlbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ahk5vlbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-yen-circle" {...props}></Icon>
