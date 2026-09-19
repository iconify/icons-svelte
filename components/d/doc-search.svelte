<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sh0yo7t6f.css';
import '../../css/w/w2yyvybiu.css';
import '../../css/g/g229fc2zp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2UEwHd1v"><g class="ft5dv1b6b"><path class="sh0yo7t6f"/><path class="w2yyvybiu"/><path class="g229fc2zp"/></g></mask></defs><path mask="url(#SVG2UEwHd1v)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:doc-search" {...props}></Icon>
