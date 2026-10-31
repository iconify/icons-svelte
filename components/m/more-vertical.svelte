<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/e-7mzjb9p.css';
import '../../css/u/u40kb3buv.css';
import '../../css/i/itw7vib_f.css';
import '../../css/l/la_zwccio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="e-7mzjb9p wm-shadow"/><path class="u40kb3buv wm-shadow"/><path class="itw7vib_f"/><path class="la_zwccio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:more-vertical" {...props}></Icon>
