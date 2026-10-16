<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaeaflbsb.css';
import '../../css/a/aa1hjvvok.css';
import '../../css/k/k1xp4kbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gaeaflbsb"/><path class="aa1hjvvok"/><path class="k1xp4kbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emissions-trading-48-bold" {...props}></Icon>
