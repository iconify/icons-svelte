<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_u2lacwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_u2lacwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:receipt-bold" {...props}></Icon>
