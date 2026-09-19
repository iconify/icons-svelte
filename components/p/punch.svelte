<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxz13rg8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lxz13rg8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:punch" {...props}></Icon>
