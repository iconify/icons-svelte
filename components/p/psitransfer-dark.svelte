<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt1s5mb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dt1s5mb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:psitransfer-dark" {...props}></Icon>
