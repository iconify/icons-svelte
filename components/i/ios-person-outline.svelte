<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsit_hb8q.css';
import '../../css/k/kdqm06bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xsit_hb8q"/><path class="kdqm06bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-person-outline" {...props}></Icon>
