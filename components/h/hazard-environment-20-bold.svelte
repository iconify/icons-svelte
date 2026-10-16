<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcia1ds6l.css';
import '../../css/i/istrjj4et.css';
import '../../css/y/y06ocpbjt.css';
import '../../css/p/pw9j91bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pcia1ds6l"/><path class="istrjj4et"/><path class="y06ocpbjt"/><path class="pw9j91bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-environment-20-bold" {...props}></Icon>
