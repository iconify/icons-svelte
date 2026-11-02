<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nclaoly9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nclaoly9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:capsule-fill" {...props}></Icon>
