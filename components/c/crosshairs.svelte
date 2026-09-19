<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxxbk6bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jxxbk6bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:crosshairs" {...props}></Icon>
