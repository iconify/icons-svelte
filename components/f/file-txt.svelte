<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-iewfb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-iewfb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-txt" {...props}></Icon>
