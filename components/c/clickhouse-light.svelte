<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4-4i3wlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m4-4i3wlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clickhouse-light" {...props}></Icon>
