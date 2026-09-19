<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq4qg5b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1568,"height":1312};
const content = `<path class="bq4qg5b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:eject" {...props}></Icon>
