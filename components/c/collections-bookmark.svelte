<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/g1pix1bws.css';
import '../../css/r/rugjrsblu.css';
import '../../css/z/z6kf3ab0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1pix1bws"/><path class="rugjrsblu"/><path class="z6kf3ab0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:collections-bookmark" {...props}></Icon>
