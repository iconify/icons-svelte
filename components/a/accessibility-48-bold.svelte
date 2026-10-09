<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2neunb3u.css';
import '../../css/y/ylciz6x-b.css';
import '../../css/s/s6ko3xcua.css';
import '../../css/p/pml7bcbbm.css';
import '../../css/t/t79v3gblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="ylciz6x-b"/><path class="s6ko3xcua"/><path class="pml7bcbbm"/><path class="t79v3gblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:accessibility-48-bold" {...props}></Icon>
