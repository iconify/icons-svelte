<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etnnq76lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etnnq76lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:align-right-box" {...props}></Icon>
