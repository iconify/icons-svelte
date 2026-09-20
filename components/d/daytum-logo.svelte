<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/t/ts9smeb3v.css';
import '../../css/v/v7x4ucb2s.css';
import '../../css/m/mg7qgd5-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="ts9smeb3v"/><path class="v7x4ucb2s"/><path class="mg7qgd5-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:daytum-logo" {...props}></Icon>
