<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkrxt4bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkrxt4bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-left-line-filled" {...props}></Icon>
