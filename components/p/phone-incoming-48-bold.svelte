<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5idgqqvy.css';
import '../../css/l/lyz0avnlk.css';
import '../../css/m/m_a345b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b5idgqqvy"/><path class="lyz0avnlk"/><path class="m_a345b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-incoming-48-bold" {...props}></Icon>
