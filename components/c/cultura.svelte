<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjp3v608l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjp3v608l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cultura" {...props}></Icon>
