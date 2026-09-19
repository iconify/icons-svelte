<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm8nr1k6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fm8nr1k6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:dislike" {...props}></Icon>
