<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6ub-1biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s6ub-1biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-alert-1-solid" {...props}></Icon>
