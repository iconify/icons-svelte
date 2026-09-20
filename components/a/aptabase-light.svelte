<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utzkmlbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="utzkmlbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aptabase-light" {...props}></Icon>
