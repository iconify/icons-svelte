<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/astguezjt.css';
import '../../css/m/m9cbxbbqp.css';
import '../../css/q/qi32o3t-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="astguezjt"/><path class="m9cbxbbqp"/><path class="qi32o3t-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:crossedflags" {...props}></Icon>
