<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct9mjbcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct9mjbcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:multiselect-line" {...props}></Icon>
