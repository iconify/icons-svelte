<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl7tz6c7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":26};
const content = `<path class="rl7tz6c7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-zip-26" {...props}></Icon>
