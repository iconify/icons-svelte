<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/dk2iqibxd.css';
import '../../css/s/sqqc6d8ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="dk2iqibxd"/><path class="sqqc6d8ws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:location-check-outline" {...props}></Icon>
