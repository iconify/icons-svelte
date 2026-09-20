<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6m_hiuih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6m_hiuih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:global-search-filled" {...props}></Icon>
