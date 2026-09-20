<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0p9_yb_k.css';
import '../../css/b/bu9ktetle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0p9_yb_k"/><path class="bu9ktetle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:office-chair-bold" {...props}></Icon>
