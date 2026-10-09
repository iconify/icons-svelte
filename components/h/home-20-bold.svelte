<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffnzzok4k.css';
import '../../css/o/obwdsybdp.css';
import '../../css/l/lrafj40nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ffnzzok4k"/><path class="obwdsybdp"/><path class="lrafj40nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:home-20-bold" {...props}></Icon>
