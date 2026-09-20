<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_a4ygk1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y_a4ygk1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:eject-solid" {...props}></Icon>
