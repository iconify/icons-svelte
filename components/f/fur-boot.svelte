<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_ob6yb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v_ob6yb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fur-boot" {...props}></Icon>
