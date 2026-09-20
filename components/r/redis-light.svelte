<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgf29cc2c.css';
import '../../css/s/s8or9-btt.css';
import '../../css/s/s-cwl4b5f.css';
import '../../css/w/wo82rkbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bgf29cc2c"/><path class="s8or9-btt"/><path class="s-cwl4b5f"/><path class="wo82rkbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redis-light" {...props}></Icon>
