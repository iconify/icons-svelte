<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf1_53b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hf1_53b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:coffee-mug-solid" {...props}></Icon>
