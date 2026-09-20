<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezfumgw-x.css';
import '../../css/n/n9z1r6vko.css';
import '../../css/c/cqqjrobdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ezfumgw-x"><path class="n9z1r6vko"/><path class="cqqjrobdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:cellular-network-5g" {...props}></Icon>
