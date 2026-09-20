<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcc6e0kab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mcc6e0kab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pulp-project-light" {...props}></Icon>
