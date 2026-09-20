<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1arq4b0h.css';
import '../../css/w/wo_8mcpow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1arq4b0h"/><path class="wo_8mcpow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:phone-locked-filled" {...props}></Icon>
