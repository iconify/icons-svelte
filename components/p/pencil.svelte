<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgmh4nbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgmh4nbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:pencil" {...props}></Icon>
