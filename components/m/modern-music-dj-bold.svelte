<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruqy2nb-z.css';
import '../../css/y/yg1-m40zm.css';
import '../../css/s/s8rs66b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruqy2nb-z"/><path class="yg1-m40zm"/><path class="s8rs66b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:modern-music-dj-bold" {...props}></Icon>
