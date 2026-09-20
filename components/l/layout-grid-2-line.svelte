<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esymu1zan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esymu1zan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-grid-2-line" {...props}></Icon>
