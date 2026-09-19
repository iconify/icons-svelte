<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxuea-bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="dxuea-bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:battery-empty" {...props}></Icon>
