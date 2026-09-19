<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek3m_ebxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek3m_ebxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:brush-cleaning" {...props}></Icon>
