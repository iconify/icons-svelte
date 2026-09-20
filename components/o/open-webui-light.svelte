<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtt4lrb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qtt4lrb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:open-webui-light" {...props}></Icon>
