<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr29-dgdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr29-dgdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gallery-horizontal-fill" {...props}></Icon>
