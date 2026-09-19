<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acpb1078r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="acpb1078r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:four-four" {...props}></Icon>
