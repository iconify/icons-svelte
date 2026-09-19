<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1ngxvwpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b1ngxvwpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hive-mind" {...props}></Icon>
