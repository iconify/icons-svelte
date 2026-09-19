<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ladta5iqv.css';
import '../../css/y/y0ij68xok.css';
import '../../css/e/er5hh2b9a.css';
import '../../css/y/ylm9uq4vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ladta5iqv"/><path class="y0ij68xok"/><path clip-rule="evenodd" class="er5hh2b9a"/><path class="ylm9uq4vm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:burn" {...props}></Icon>
