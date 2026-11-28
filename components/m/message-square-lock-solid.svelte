<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt4nd8izy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt4nd8izy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-lock-solid" {...props}></Icon>
