<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nihuu_b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="nihuu_b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:id-badge" {...props}></Icon>
