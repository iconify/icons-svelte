<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-bp5m_2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-bp5m_2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:login-circle-fill" {...props}></Icon>
