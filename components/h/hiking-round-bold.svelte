<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmd2tzwfv.css';
import '../../css/c/c_tiz1b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmd2tzwfv"/><path clip-rule="evenodd" class="c_tiz1b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hiking-round-bold" {...props}></Icon>
