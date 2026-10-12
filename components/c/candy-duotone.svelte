<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z_-r70b7z.css';
import '../../css/a/axfcjcbgh.css';
import '../../css/u/ua_sik_-v.css';
import '../../css/p/pfbai9q-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z_-r70b7z"/><path class="axfcjcbgh"/><path class="ua_sik_-v"/><path class="pfbai9q-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:candy-duotone" {...props}></Icon>
