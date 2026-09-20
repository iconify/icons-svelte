<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sms47jbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sms47jbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:featured-playlist-fill" {...props}></Icon>
