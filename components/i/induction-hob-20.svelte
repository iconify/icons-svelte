<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co0vf9bvy.css';
import '../../css/e/ec1om73-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="co0vf9bvy"/><path class="ec1om73-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:induction-hob-20" {...props}></Icon>
