<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw_efn0ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hw_efn0ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-alp-dark" {...props}></Icon>
