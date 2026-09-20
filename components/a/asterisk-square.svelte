<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7xpl2p_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7xpl2p_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:asterisk-square" {...props}></Icon>
