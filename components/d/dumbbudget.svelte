<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2o6txvom.css';
import '../../css/s/syec1nbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="v2o6txvom"/><path class="syec1nbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbbudget" {...props}></Icon>
