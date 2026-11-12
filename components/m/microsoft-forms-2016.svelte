<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znoie2bjy.css';
import '../../css/g/g15pwcbhu.css';
import '../../css/e/evac21bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="znoie2bjy"/><path class="g15pwcbhu"/><path class="evac21bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-forms-2016" {...props}></Icon>
