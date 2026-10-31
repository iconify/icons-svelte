<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/d7_8r7b7c.css';
import '../../css/m/mcd_p02bq.css';
import '../../css/k/k41b5wbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="d7_8r7b7c wm-shadow"/><path class="mcd_p02bq wm-shadow"/><path class="k41b5wbvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:atom" {...props}></Icon>
