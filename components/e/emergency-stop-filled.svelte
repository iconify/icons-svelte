<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv36f1m1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv36f1m1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:emergency-stop-filled" {...props}></Icon>
