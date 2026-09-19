<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvylydb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvylydb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:home-alt-filled" {...props}></Icon>
