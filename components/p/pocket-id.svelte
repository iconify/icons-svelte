<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iycln-b8i.css';
import '../../css/a/art3-jbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="iycln-b8i"/><path class="art3-jbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pocket-id" {...props}></Icon>
