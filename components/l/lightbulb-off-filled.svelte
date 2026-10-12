<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulblegbmg.css';
import '../../css/f/fszydxb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulblegbmg"/><path class="fszydxb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lightbulb-off-filled" {...props}></Icon>
