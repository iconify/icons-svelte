<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h88y73pra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="h88y73pra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:chairlift" {...props}></Icon>
