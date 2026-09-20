<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_g86w7hz.css';
import '../../css/d/drsj4us_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_g86w7hz"/><path class="drsj4us_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:car-2" {...props}></Icon>
