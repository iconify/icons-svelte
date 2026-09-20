<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_fowhusy.css';
import '../../css/q/qccz5acbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_fowhusy"/><path class="qccz5acbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dext" {...props}></Icon>
