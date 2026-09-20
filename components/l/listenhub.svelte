<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf1vx18wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1vx18wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:listenhub" {...props}></Icon>
