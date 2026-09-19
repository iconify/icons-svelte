<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wua8ckbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wua8ckbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brightness-filled" {...props}></Icon>
