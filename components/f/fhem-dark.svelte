<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th92ccbsb.css';
import '../../css/l/lbnij82qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="th92ccbsb"/><path class="lbnij82qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fhem-dark" {...props}></Icon>
