<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cep5rxtrl.css';
import '../../css/s/syec1nbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="cep5rxtrl"/><path class="syec1nbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbbudget" {...props}></Icon>
