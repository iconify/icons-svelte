<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/b/b5cxlbb9z.css';
import '../../css/s/s1i6yv5uk.css';
import '../../css/k/k-e2t9i7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="b5cxlbb9z"/><path class="s1i6yv5uk"/><path class="k-e2t9i7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pressure" {...props}></Icon>
