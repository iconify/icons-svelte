<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgi6od49b.css';
import '../../css/f/fev25zbss.css';
import '../../css/c/cktwblots.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgi6od49b"/><path class="fev25zbss"/><path class="cktwblots"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:human-resources-search-employees-bold" {...props}></Icon>
