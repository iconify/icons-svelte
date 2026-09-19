<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgydwwb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":795,"height":776};
const content = `<path class="lgydwwb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:g-upper-case" {...props}></Icon>
