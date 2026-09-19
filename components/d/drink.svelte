<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp23nzbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qp23nzbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:drink" {...props}></Icon>
