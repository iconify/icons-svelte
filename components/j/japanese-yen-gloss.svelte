<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ball2zbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ball2zbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:japanese-yen-gloss" {...props}></Icon>
