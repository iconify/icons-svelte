<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp3q74byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qp3q74byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mono" {...props}></Icon>
