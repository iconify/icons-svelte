<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm5cwzkri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nm5cwzkri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mute" {...props}></Icon>
