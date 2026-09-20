<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/dabc3ybij.css';
import '../../css/g/geoysppjk.css';
import '../../css/u/uzzwf3bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dabc3ybij"/><path class="geoysppjk"/><path class="uzzwf3bzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:road-sign-hairpin-turn-left" {...props}></Icon>
