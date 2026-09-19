<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv_ezp8gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv_ezp8gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:magic-wand-04" {...props}></Icon>
