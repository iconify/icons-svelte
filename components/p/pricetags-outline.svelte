<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neoc4fbwo.css';
import '../../css/u/ui33wlb3m.css';
import '../../css/m/midf3bbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="neoc4fbwo"/><path class="ui33wlb3m"/><path class="midf3bbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pricetags-outline" {...props}></Icon>
