<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3qadv63d.css';
import '../../css/p/p3nhuib5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a3qadv63d"/><path class="p3nhuib5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-to-line-20" {...props}></Icon>
