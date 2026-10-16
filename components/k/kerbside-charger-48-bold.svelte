<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brf4rlr5x.css';
import '../../css/n/nd0pwk2rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="brf4rlr5x"/><path class="nd0pwk2rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kerbside-charger-48-bold" {...props}></Icon>
