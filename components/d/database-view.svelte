<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9nupwb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f9nupwb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:database-view" {...props}></Icon>
