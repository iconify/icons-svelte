<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/k/krz1plydf.css';
import '../../css/d/dv30fkbev.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNtYAwbSA"><g class="ufeehvblu"><path class="krz1plydf"/><path class="dv30fkbev"/></g></mask></defs><path mask="url(#SVGNtYAwbSA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:folder-minus" {...props}></Icon>
