<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s52to77mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="s52to77mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:a-outline" {...props}></Icon>
