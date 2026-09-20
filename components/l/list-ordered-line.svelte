<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdb262e9z.css';
import '../../css/s/svs9u_b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdb262e9z"/><path class="svs9u_b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-ordered-line" {...props}></Icon>
