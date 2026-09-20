<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/povo_89as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="povo_89as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-tinder" {...props}></Icon>
