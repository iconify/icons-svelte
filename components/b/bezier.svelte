<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we9h4vbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="we9h4vbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bezier" {...props}></Icon>
