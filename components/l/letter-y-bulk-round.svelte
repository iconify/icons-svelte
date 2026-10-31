<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_p24pbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_p24pbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-y-bulk-round" {...props}></Icon>
