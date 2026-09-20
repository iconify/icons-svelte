<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/h3jxylb7z.css';
import '../../css/a/aw3yw1bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="h3jxylb7z"/><path class="aw3yw1bae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-plus-duotone" {...props}></Icon>
