<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcq1m_bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xcq1m_bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-pickup" {...props}></Icon>
