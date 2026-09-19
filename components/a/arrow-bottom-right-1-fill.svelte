<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgo3wgb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgo3wgb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-right-1-fill" {...props}></Icon>
