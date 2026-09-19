<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/b/bcqa_q4nr.css';
import '../../css/j/jxw8wmbdq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpsWnyehb"><g class="ufeehvblu"><path class="bcqa_q4nr"/><path class="jxw8wmbdq"/></g></mask></defs><path mask="url(#SVGpsWnyehb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:folder-download" {...props}></Icon>
