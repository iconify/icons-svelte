<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yul3m_bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yul3m_bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dice-fill-round" {...props}></Icon>
