<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urn_w85ht.css';
import '../../css/l/ldest115k.css';
import '../../css/n/n_64_tbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="urn_w85ht"/><path class="ldest115k"/><path class="n_64_tbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:duplicate" {...props}></Icon>
