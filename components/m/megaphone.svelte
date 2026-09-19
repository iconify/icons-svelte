<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqtyu2b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lqtyu2b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:megaphone" {...props}></Icon>
