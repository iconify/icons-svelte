<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lmoo01bav.css';
import '../../css/k/k5rx2ix5o.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGyZNfyd1N"><g class="ufeehvblu"><path class="lmoo01bav"/><path class="k5rx2ix5o"/></g></mask></defs><path mask="url(#SVGyZNfyd1N)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:application-one" {...props}></Icon>
