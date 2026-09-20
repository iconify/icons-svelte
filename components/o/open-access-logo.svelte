<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/l/lll-uetsu.css';
import '../../css/o/ovjw8ab9k.css';
import '../../css/i/ibejhacsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="lll-uetsu"/><path class="ovjw8ab9k"/><path class="ibejhacsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:open-access-logo" {...props}></Icon>
