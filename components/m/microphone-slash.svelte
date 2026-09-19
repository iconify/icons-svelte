<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx8hyq68k.css';
import '../../css/v/v3ruk_beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx8hyq68k"/><path class="v3ruk_beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microphone-slash" {...props}></Icon>
