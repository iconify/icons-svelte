<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz9t_ne3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sz9t_ne3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:mail-send-email-message-solid" {...props}></Icon>
