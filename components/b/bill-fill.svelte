<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0-33ebmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0-33ebmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bill-fill" {...props}></Icon>
