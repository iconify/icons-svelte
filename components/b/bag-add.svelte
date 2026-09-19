<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzp4omb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zzp4omb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bag-add" {...props}></Icon>
