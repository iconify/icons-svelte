<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we596nb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we596nb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:honour-line" {...props}></Icon>
