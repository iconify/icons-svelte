<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncgeo_vzx.css';
import '../../css/g/glg0knb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ncgeo_vzx"/><path class="glg0knb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:localess" {...props}></Icon>
