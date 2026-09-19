<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iync2tbfi.css';
import '../../css/m/mygm3kb3e.css';
import '../../css/v/voqtyp18f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="iync2tbfi"/><path class="mygm3kb3e"/><ellipse transform="rotate(30 23.477 12.594)" class="voqtyp18f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:red-heart" {...props}></Icon>
