<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye6mt9rky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ye6mt9rky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:circle-information-filled" {...props}></Icon>
