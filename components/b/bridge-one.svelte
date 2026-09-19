<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m874v74cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m874v74cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bridge-one" {...props}></Icon>
