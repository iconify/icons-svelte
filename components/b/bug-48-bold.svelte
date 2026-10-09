<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlukkybbv.css';
import '../../css/v/v11awfbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rlukkybbv"/><path class="v11awfbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bug-48-bold" {...props}></Icon>
