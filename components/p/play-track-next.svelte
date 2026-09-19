<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grjom1bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grjom1bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:play-track-next" {...props}></Icon>
