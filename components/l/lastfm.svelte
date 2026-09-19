<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmpb--8va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dmpb--8va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:lastfm" {...props}></Icon>
