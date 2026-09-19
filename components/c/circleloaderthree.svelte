<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6yhc8bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="g6yhc8bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleloaderthree" {...props}></Icon>
