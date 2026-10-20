<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nr8xmjbyq.css';
import '../../css/r/rtunwgx1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nr8xmjbyq"/><path class="rtunwgx1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:package-open" {...props}></Icon>
