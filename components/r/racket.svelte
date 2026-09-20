<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suwe9-r6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suwe9-r6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:racket" {...props}></Icon>
