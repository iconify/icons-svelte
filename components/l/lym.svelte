<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmx0tgbbf.css';
import '../../css/m/mxx-s1b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmx0tgbbf"/><path class="mxx-s1b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lym" {...props}></Icon>
