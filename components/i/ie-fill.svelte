<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp3lv5b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp3lv5b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ie-fill" {...props}></Icon>
