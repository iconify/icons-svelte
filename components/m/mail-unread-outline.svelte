<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug7viwfag.css';
import '../../css/a/atf7rkfzt.css';
import '../../css/s/sntxj5r0a.css';
import '../../css/b/bvllc8w-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ug7viwfag"/><path class="atf7rkfzt"/><circle class="sntxj5r0a"/><path class="bvllc8w-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mail-unread-outline" {...props}></Icon>
