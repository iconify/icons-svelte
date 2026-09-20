<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh13jvbja.css';
import '../../css/m/mdi0c_bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh13jvbja"/><path class="mdi0c_bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:page-tab-filled" {...props}></Icon>
