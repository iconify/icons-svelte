<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kggteebzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kggteebzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-text-multiple-outline" {...props}></Icon>
