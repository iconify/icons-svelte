<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k71by3b1k.css';
import '../../css/o/obq3yybhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="k71by3b1k"/><path class="obq3yybhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:contrast-outline" {...props}></Icon>
