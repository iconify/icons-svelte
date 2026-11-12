<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyun3dd4z.css';
import '../../css/h/hfnpruahq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lyun3dd4z"/><path class="hfnpruahq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-s3-light" {...props}></Icon>
