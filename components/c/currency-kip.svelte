<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkoh_wbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkoh_wbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-kip" {...props}></Icon>
