<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz__e2bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lz__e2bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pirate-grave" {...props}></Icon>
