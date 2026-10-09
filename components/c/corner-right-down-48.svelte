<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4zhywu2u.css';
import '../../css/s/sbj00_4pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p4zhywu2u"/><path class="sbj00_4pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-right-down-48" {...props}></Icon>
