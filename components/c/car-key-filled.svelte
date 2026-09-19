<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct3bt8zjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct3bt8zjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:car-key-filled" {...props}></Icon>
