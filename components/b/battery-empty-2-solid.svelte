<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy380gv4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oy380gv4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-empty-2-solid" {...props}></Icon>
