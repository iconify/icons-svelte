<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpkjnpb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpkjnpb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:decrypted-check-outline" {...props}></Icon>
