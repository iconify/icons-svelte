<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psd2cpt5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psd2cpt5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:pulse" {...props}></Icon>
