<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zlov1rylm.css';
import '../../css/y/ypus4vb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="zlov1rylm"/><path class="ypus4vb-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:browser-duotone" {...props}></Icon>
