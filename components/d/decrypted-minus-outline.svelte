<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg0y5xmtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg0y5xmtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:decrypted-minus-outline" {...props}></Icon>
