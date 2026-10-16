<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zen2agbyu.css';
import '../../css/v/v53qj5w7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zen2agbyu"/><path class="v53qj5w7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:disc-48" {...props}></Icon>
