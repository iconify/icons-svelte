<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-gvyg65x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g-gvyg65x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:loading-four" {...props}></Icon>
