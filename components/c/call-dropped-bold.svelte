<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_hf_9u3p.css';
import '../../css/a/autb8mb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_hf_9u3p"/><path class="autb8mb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-dropped-bold" {...props}></Icon>
