<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpn_zqbzh.css';
import '../../css/r/rcaxrbcwv.css';
import '../../css/k/k2_638ciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpn_zqbzh"/><path class="rcaxrbcwv"/><path class="k2_638ciz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers" {...props}></Icon>
