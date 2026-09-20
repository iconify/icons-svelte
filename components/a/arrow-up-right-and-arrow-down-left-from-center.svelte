<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp_4n9bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kp_4n9bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrow-up-right-and-arrow-down-left-from-center" {...props}></Icon>
