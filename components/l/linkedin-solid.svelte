<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgazo6tfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mgazo6tfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:linkedin-solid" {...props}></Icon>
