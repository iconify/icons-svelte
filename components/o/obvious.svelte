<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq5wtgblw.css';
import '../../css/c/cxplgm_hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq5wtgblw"/><path clip-rule="evenodd" class="cxplgm_hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:obvious" {...props}></Icon>
