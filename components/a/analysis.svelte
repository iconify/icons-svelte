<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae5_81b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ae5_81b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:analysis" {...props}></Icon>
