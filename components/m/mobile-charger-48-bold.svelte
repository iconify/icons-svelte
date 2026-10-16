<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcjo-6bpf.css';
import '../../css/g/gjx6_nbye.css';
import '../../css/f/f9s4ogcoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gcjo-6bpf"/><path class="gjx6_nbye"/><path class="f9s4ogcoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mobile-charger-48-bold" {...props}></Icon>
