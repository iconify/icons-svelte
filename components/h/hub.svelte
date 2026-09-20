<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0yut_mvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0yut_mvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hub" {...props}></Icon>
