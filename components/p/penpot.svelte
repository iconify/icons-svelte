<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebyhwubyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ebyhwubyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:penpot" {...props}></Icon>
