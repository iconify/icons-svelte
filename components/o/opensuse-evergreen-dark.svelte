<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djf9zbitb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="djf9zbitb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-evergreen-dark" {...props}></Icon>
