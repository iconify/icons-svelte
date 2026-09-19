<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q62dic9ok.css';
import '../../css/k/k-dpg_bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q62dic9ok"/><path class="k-dpg_bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-playstation" {...props}></Icon>
