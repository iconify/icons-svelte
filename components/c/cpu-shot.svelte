<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ygskbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n_ygskbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cpu-shot" {...props}></Icon>
