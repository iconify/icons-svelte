<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi10br14x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mi10br14x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:emptynotepage" {...props}></Icon>
