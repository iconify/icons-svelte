<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rghi9ibtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rghi9ibtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:device-tablet-portrait" {...props}></Icon>
