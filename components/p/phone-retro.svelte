<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oy6xs-ufv.css';
import '../../css/z/z5xnn5lxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oy6xs-ufv"/><path clip-rule="evenodd" class="z5xnn5lxq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:phone-retro" {...props}></Icon>
