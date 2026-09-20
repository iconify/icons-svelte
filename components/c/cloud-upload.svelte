<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l721n2bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l721n2bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cloud-upload" {...props}></Icon>
