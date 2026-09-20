<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa1ikb5de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa1ikb5de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:ethernet-port-bold" {...props}></Icon>
