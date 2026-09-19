<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/w/wuu1i6jkg.css';
import '../../css/b/bmkkjed5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="wuu1i6jkg"/><path class="bmkkjed5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-yes-light" {...props}></Icon>
