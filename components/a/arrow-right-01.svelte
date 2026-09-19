<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enuqh9v5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enuqh9v5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-right-01" {...props}></Icon>
