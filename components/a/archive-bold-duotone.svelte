<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ileo9db7a.css';
import '../../css/i/i3l80h-5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ileo9db7a"/><path class="i3l80h-5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-bold-duotone" {...props}></Icon>
