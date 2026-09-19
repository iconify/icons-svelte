<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bdwf75b_m.css';
import '../../css/c/c2_tw-byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="bdwf75b_m"/><path class="c2_tw-byy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:award-outline" {...props}></Icon>
