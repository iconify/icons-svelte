<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-4rqjbfm.css';
import '../../css/h/h1xc_8yrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t-4rqjbfm"/><path class="h1xc_8yrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-network-48-bold" {...props}></Icon>
