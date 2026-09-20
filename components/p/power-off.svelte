<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epagx4b5c.css';
import '../../css/o/odq3bckdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epagx4b5c"/><path class="odq3bckdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:power-off" {...props}></Icon>
