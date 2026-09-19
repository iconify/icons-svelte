<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/b0a7tkekm.css';
import '../../css/b/b946ibi6z.css';
import '../../css/m/mzqewjw4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b0a7tkekm"/><path class="b946ibi6z"/><path class="mzqewjw4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:real-estate-01" {...props}></Icon>
