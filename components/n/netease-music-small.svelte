<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu7f6s55p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iu7f6s55p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:netease-music-small" {...props}></Icon>
