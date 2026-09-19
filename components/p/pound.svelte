<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uinlmobua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uinlmobua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pound" {...props}></Icon>
