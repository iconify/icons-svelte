<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9m_iyplt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9m_iyplt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:chevron-left-expressive" {...props}></Icon>
