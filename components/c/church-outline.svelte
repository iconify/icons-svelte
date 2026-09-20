<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9o9rzqzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9o9rzqzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:church-outline" {...props}></Icon>
