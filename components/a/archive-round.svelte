<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usxs_kptd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usxs_kptd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:archive-round" {...props}></Icon>
