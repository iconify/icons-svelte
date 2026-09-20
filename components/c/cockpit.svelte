<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2jjn5_7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2jjn5_7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cockpit" {...props}></Icon>
