<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhi3crign.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qhi3crign"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:donkey" {...props}></Icon>
