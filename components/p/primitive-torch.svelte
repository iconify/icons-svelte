<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkt9d2bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kkt9d2bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:primitive-torch" {...props}></Icon>
