<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atr_g023t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atr_g023t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:lock-on-filled" {...props}></Icon>
