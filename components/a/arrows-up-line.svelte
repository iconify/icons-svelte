<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbn1m_afc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbn1m_afc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-up-line" {...props}></Icon>
