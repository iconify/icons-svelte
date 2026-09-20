<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gel_m_b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gel_m_b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-shield-fill" {...props}></Icon>
