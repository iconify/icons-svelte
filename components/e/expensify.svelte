<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw0enn4mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw0enn4mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:expensify" {...props}></Icon>
