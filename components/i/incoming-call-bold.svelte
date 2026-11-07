<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_hf_9u3p.css';
import '../../css/g/gwsx06brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_hf_9u3p"/><path class="gwsx06brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:incoming-call-bold" {...props}></Icon>
