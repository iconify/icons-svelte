<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la79tccyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la79tccyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:certificate-filled" {...props}></Icon>
