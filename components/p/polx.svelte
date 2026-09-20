<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/t/tj_0_pghw.css';
import '../../css/v/v1t3gdcyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="tj_0_pghw"/><path class="v1t3gdcyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:polx" {...props}></Icon>
