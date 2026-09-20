<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g16uogwjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g16uogwjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-warning-solid" {...props}></Icon>
