<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvuozgpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwvuozgpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:keyframe-align-vertical" {...props}></Icon>
