<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr1mw-09t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr1mw-09t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-alt-1-fill-round" {...props}></Icon>
