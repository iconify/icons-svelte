<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cut31abpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cut31abpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:eye-off-fill" {...props}></Icon>
