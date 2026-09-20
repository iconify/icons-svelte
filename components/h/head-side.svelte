<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj_jdibkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj_jdibkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:head-side" {...props}></Icon>
