<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hds5-ov_u.css';
import '../../css/t/t4y2m7bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="hds5-ov_u"/><path class="t4y2m7bli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-arrow-left-duotone" {...props}></Icon>
