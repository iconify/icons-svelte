<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k90nvltuk.css';
import '../../css/w/w678ji4gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k90nvltuk"/><path class="w678ji4gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-wallet" {...props}></Icon>
