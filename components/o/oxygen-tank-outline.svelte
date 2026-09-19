<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaiqkpb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oaiqkpb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:oxygen-tank-outline" {...props}></Icon>
