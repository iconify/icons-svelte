<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-zz1ta_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n-zz1ta_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:align-text-both" {...props}></Icon>
