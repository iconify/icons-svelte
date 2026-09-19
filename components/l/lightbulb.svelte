<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baqr00whe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="baqr00whe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:lightbulb" {...props}></Icon>
