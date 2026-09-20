<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq7w9gcux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wq7w9gcux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-prime" {...props}></Icon>
