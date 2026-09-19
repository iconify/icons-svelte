<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3kb4cgpl.css';
import '../../css/w/wuu1i6jkg.css';
import '../../css/m/mfk1l-r5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="r3kb4cgpl"><path class="wuu1i6jkg"/><path class="mfk1l-r5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-add-bold" {...props}></Icon>
