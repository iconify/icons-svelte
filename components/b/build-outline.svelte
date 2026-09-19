<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbsfahbqu.css';
import '../../css/c/cdb_1wbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sbsfahbqu"/><circle class="cdb_1wbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:build-outline" {...props}></Icon>
