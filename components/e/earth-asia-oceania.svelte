<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx5v6zsnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lx5v6zsnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:earth-asia-oceania" {...props}></Icon>
