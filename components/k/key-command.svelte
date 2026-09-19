<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb-4b9ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb-4b9ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:key-command" {...props}></Icon>
