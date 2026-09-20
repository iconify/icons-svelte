<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq5mdzb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq5mdzb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:profile-line" {...props}></Icon>
