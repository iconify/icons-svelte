<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q55j-hbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1280};
const content = `<path class="q55j-hbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mobile-phone" {...props}></Icon>
