<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v351mchmy.css';
import '../../css/y/yjcru9-ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v351mchmy"/><path class="yjcru9-ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monopile-48" {...props}></Icon>
