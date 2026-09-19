<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-wfxjb1n.css';
import '../../css/f/fajrh4bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-wfxjb1n"/><path class="fajrh4bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-minus" {...props}></Icon>
