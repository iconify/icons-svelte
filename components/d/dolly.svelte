<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd6-kdbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nd6-kdbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dolly" {...props}></Icon>
