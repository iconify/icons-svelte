<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceyh5fb6m.css';
import '../../css/l/lktrzctrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ceyh5fb6m"/><path class="lktrzctrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filegator-light" {...props}></Icon>
