<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h38o_z5yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h38o_z5yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:drop-zone" {...props}></Icon>
