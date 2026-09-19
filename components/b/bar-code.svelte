<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aylov_bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aylov_bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bar-code" {...props}></Icon>
