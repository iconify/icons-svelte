<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aixq4db0w.css';
import '../../css/d/deb9mesxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aixq4db0w"/><path class="deb9mesxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:emptydocument" {...props}></Icon>
