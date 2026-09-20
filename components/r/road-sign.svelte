<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bzanpxylq.css';
import '../../css/q/qdnrthbhb.css';
import '../../css/f/f6hdy3bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bzanpxylq"/><path class="qdnrthbhb"/><path class="f6hdy3bdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:road-sign" {...props}></Icon>
