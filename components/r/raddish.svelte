<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo_lgwbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qo_lgwbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:raddish" {...props}></Icon>
