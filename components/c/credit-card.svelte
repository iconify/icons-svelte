<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx6f9ibwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx6f9ibwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:credit-card" {...props}></Icon>
