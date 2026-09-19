<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvw82kb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zvw82kb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:reload-gun-barrel" {...props}></Icon>
