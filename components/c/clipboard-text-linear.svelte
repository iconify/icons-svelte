<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lz14ttf8r.css';
import '../../css/x/x_757hbgu.css';
import '../../css/u/ujkefybfc.css';
import '../../css/m/m390b8qby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lz14ttf8r"/><path class="x_757hbgu"/><path class="ujkefybfc"/><path class="m390b8qby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-text-linear" {...props}></Icon>
