<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxab02pny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxab02pny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:no-gas-station" {...props}></Icon>
