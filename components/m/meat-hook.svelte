<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsrr6zzpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xsrr6zzpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:meat-hook" {...props}></Icon>
