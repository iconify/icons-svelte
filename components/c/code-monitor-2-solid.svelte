<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_0v8sb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f_0v8sb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:code-monitor-2-solid" {...props}></Icon>
