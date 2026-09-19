<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw7n_3bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bw7n_3bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lucky-fisherman" {...props}></Icon>
