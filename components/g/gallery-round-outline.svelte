<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvimm4bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvimm4bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-round-outline" {...props}></Icon>
