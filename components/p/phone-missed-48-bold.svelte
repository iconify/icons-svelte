<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny2audwvu.css';
import '../../css/l/lyhfxv6br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ny2audwvu"/><path class="lyhfxv6br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-missed-48-bold" {...props}></Icon>
