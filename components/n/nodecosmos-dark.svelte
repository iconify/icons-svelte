<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oadbqx5tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oadbqx5tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nodecosmos-dark" {...props}></Icon>
