<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svjygv55w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="svjygv55w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:etcd-dark" {...props}></Icon>
