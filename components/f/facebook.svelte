<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd2-gvknj.css';
import '../../css/n/niw2nrbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vd2-gvknj"/><path class="niw2nrbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:facebook" {...props}></Icon>
