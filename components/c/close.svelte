<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opd2-3bgk.css';
import '../../css/u/uuunrrbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="opd2-3bgk"/><path class="uuunrrbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:close" {...props}></Icon>
