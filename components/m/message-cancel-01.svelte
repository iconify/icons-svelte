<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxsr6dk8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxsr6dk8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-cancel-01" {...props}></Icon>
