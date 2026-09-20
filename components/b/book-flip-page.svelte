<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9wtmta2j.css';
import '../../css/v/valpkebar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9wtmta2j"/><path class="valpkebar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:book-flip-page" {...props}></Icon>
