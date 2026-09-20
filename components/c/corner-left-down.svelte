<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv3fe1b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kv3fe1b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:corner-left-down" {...props}></Icon>
