<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykqjh5npp.css';
import '../../css/t/tvigq4bta.css';
import '../../css/l/lspatcbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ykqjh5npp"/><path class="tvigq4bta"/><path class="lspatcbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-chk-dark" {...props}></Icon>
