<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esqg6lffk.css';
import '../../css/m/m_dyr3b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="esqg6lffk"/><path class="m_dyr3b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:power" {...props}></Icon>
