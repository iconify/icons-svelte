<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwlek8bjm.css';
import '../../css/o/onp3hbbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jwlek8bjm"/><path class="onp3hbbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:italic-48" {...props}></Icon>
