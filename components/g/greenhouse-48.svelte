<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mytv6xbyl.css';
import '../../css/v/va8q5vg9j.css';
import '../../css/y/y8j-xvbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mytv6xbyl"/><path class="va8q5vg9j"/><path class="y8j-xvbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:greenhouse-48" {...props}></Icon>
