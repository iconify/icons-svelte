<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiop7zcov.css';
import '../../css/s/s9vs66t3i.css';
import '../../css/o/oqmockrge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wiop7zcov"/><path class="s9vs66t3i"/><path class="oqmockrge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mq-1x1" {...props}></Icon>
