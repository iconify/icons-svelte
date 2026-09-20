<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3j4blber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3j4blber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:caret-right" {...props}></Icon>
