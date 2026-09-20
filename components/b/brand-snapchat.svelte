<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_yc0s4am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_yc0s4am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-snapchat" {...props}></Icon>
