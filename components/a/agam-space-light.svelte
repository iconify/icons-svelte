<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/autdh0b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="autdh0b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agam-space-light" {...props}></Icon>
