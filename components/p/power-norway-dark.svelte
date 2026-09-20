<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kddhxzb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kddhxzb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:power-norway-dark" {...props}></Icon>
