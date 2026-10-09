<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaeaflbsb.css';
import '../../css/q/q2s99zbjl.css';
import '../../css/i/igpss3xso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gaeaflbsb"/><path class="q2s99zbjl"/><path class="igpss3xso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-trading-48-bold" {...props}></Icon>
