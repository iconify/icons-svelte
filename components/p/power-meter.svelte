<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpvwby7ij.css';
import '../../css/h/h1qw7gi7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lpvwby7ij"/><path class="h1qw7gi7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:power-meter" {...props}></Icon>
