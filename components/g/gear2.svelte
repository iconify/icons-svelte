<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/pezxs9bin.css';
import '../../css/b/b10du-zvb.css';
import '../../css/f/fa3gx-2-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pezxs9bin"/><circle class="b10du-zvb"/><path class="fa3gx-2-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gear2" {...props}></Icon>
