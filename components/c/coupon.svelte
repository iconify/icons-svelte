<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/n/n4pernbka.css';
import '../../css/x/x7s0ksbho.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlnImqe7h"><g class="ufeehvblu"><path class="n4pernbka"/><path class="x7s0ksbho"/></g></mask></defs><path mask="url(#SVGlnImqe7h)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:coupon" {...props}></Icon>
