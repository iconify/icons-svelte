<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghe6iqpty.css';
import '../../css/e/ez7xqcrkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ghe6iqpty"/><path class="ez7xqcrkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-combo-48-bold" {...props}></Icon>
