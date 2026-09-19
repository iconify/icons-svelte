<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoyumsw5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qoyumsw5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-left" {...props}></Icon>
