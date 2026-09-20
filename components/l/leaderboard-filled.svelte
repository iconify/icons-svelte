<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b361owb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b361owb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:leaderboard-filled" {...props}></Icon>
