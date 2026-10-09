<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghe6iqpty.css';
import '../../css/f/fqoptnsed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ghe6iqpty"/><path class="fqoptnsed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-waterfall-48-bold" {...props}></Icon>
