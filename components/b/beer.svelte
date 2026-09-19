<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oco-8fb8g.css';
import '../../css/t/tk-rzp94k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oco-8fb8g"/><path class="tk-rzp94k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:beer" {...props}></Icon>
