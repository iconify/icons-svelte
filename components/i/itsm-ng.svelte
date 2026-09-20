<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx9a5uh8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zx9a5uh8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:itsm-ng" {...props}></Icon>
