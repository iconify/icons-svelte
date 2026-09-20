<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxb7bva-l.css';
import '../../css/m/m6c-bbbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxb7bva-l"/><path class="m6c-bbbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bolt" {...props}></Icon>
