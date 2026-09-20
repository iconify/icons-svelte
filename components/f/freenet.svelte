<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja_g3ob0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja_g3ob0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:freenet" {...props}></Icon>
