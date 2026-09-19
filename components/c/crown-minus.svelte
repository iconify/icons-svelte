<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk7ocbcqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk7ocbcqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:crown-minus" {...props}></Icon>
