<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jesu8kbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jesu8kbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:book-plus" {...props}></Icon>
