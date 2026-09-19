<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppab5wbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppab5wbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:certificate-check" {...props}></Icon>
