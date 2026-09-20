<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyvvhh_7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyvvhh_7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:game-2-line" {...props}></Icon>
