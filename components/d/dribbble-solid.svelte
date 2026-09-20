<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eislsacga.css';
import '../../css/h/hmcun9bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eislsacga"/><path class="hmcun9bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:dribbble-solid" {...props}></Icon>
