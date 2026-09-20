<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znrnh_b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="znrnh_b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:command-solid" {...props}></Icon>
