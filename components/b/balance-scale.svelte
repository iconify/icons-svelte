<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kof1pjl2v.css';
import '../../css/w/w6rc0es0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kof1pjl2v"/><path class="w6rc0es0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:balance-scale" {...props}></Icon>
