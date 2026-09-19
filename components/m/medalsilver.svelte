<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekcwtkbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1025};
const content = `<path class="ekcwtkbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:medalsilver" {...props}></Icon>
