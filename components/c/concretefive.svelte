<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk-v_9b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":895,"height":1024};
const content = `<path class="nk-v_9b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:concretefive" {...props}></Icon>
