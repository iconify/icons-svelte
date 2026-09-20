<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygez5ob8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygez5ob8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:angle-down-light" {...props}></Icon>
