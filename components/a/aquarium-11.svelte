<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzjfszbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="hzjfszbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:aquarium-11" {...props}></Icon>
