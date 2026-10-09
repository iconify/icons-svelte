<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijgh9kb6y.css';
import '../../css/r/r409soybt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ijgh9kb6y"/><path class="r409soybt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-48" {...props}></Icon>
