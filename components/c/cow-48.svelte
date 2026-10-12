<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxvst7bbl.css';
import '../../css/s/syk3pwbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qxvst7bbl"/><path class="syk3pwbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cow-48" {...props}></Icon>
