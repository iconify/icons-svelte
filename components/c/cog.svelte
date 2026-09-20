<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn_3m2b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kn_3m2b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cog" {...props}></Icon>
