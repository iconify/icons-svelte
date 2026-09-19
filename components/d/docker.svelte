<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4q9k1w2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4q9k1w2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:docker" {...props}></Icon>
