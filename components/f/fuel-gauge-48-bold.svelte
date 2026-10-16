<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw9esif9u.css';
import '../../css/i/ikm4i4bwb.css';
import '../../css/s/s0mrvwbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sw9esif9u"/><path class="ikm4i4bwb"/><path class="s0mrvwbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-gauge-48-bold" {...props}></Icon>
