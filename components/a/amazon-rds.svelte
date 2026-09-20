<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axkw0ac2k.css';
import '../../css/a/aytd6oskt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="axkw0ac2k"/><path class="aytd6oskt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-rds" {...props}></Icon>
