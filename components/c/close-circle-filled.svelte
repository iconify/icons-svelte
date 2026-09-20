<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma-rekbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma-rekbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:close-circle-filled" {...props}></Icon>
