<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/movjw89ew.css';
import '../../css/a/ax9g9_14z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="movjw89ew"/><path class="ax9g9_14z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:login-bold" {...props}></Icon>
