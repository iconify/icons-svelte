<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znvs6w-8g.css';
import '../../css/d/d2zz1uo2x.css';
import '../../css/l/l5j5uofki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="znvs6w-8g"/><path class="d2zz1uo2x"/><path class="l5j5uofki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:hidden" {...props}></Icon>
