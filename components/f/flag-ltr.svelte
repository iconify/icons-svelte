<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h05hsvrra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h05hsvrra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:flag-ltr" {...props}></Icon>
