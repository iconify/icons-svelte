<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu0zqnbaj.css';
import '../../css/n/nk5nmmbrn.css';
import '../../css/q/qm9ru_b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fu0zqnbaj"/><path class="nk5nmmbrn"/><path class="qm9ru_b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-fault-20" {...props}></Icon>
