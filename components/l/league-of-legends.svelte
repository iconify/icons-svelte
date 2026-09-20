<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3v1cfbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3v1cfbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:league-of-legends" {...props}></Icon>
