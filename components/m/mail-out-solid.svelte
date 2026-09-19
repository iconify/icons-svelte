<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u665ban.css';
import '../../css/b/bil7h4hxb.css';
import '../../css/k/k0v0v9boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="bil7h4hxb"/><path clip-rule="evenodd" class="k0v0v9boq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:mail-out-solid" {...props}></Icon>
