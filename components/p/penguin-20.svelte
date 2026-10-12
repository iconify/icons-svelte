<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l94gcsbcw.css';
import '../../css/m/m79wssnno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l94gcsbcw"/><path class="m79wssnno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:penguin-20" {...props}></Icon>
