<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwaaf0-ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwaaf0-ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:minus-square" {...props}></Icon>
