<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_66qz3oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_66qz3oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:farm" {...props}></Icon>
