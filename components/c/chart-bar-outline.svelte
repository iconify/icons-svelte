<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok6n68p5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok6n68p5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:chart-bar-outline" {...props}></Icon>
