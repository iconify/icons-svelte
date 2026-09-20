<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgxcpmbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qgxcpmbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:edit-1-outline" {...props}></Icon>
