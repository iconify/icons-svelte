<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcpth-wqs.css';
import '../../css/r/rmslx6b5x.css';
import '../../css/b/bzun-yi8p.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wcpth-wqs"/><path class="rmslx6b5x"/><path class="bzun-yi8p"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-mali" {...props}></Icon>
