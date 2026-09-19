<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfsug6rjk.css';
import '../../css/j/jej7e325s.css';
import '../../css/f/fpvpjcd5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="qfsug6rjk"/><path class="jej7e325s"/><path class="fpvpjcd5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:bell" {...props}></Icon>
