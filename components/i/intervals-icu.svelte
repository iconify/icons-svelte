<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcdlw7auy.css';
import '../../css/s/s_jmxibuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="kcdlw7auy"/><path class="s_jmxibuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:intervals-icu" {...props}></Icon>
