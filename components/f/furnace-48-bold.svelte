<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g44ax6v6c.css';
import '../../css/i/ihmii9b0s.css';
import '../../css/w/w151_7bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g44ax6v6c"/><path class="ihmii9b0s"/><path class="w151_7bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:furnace-48-bold" {...props}></Icon>
