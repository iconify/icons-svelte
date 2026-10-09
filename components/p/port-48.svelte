<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glg0ud-ue.css';
import '../../css/e/e4gy22yti.css';
import '../../css/o/oejtqxnux.css';
import '../../css/u/uge5j2d4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="glg0ud-ue"/><path class="e4gy22yti"/><path class="oejtqxnux"/><path class="uge5j2d4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:port-48" {...props}></Icon>
