<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnlhaj0by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnlhaj0by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-circle-fill" {...props}></Icon>
