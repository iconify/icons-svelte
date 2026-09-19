<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja3el70qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja3el70qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:arch" {...props}></Icon>
