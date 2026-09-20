<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz4bzpbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yz4bzpbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-diving-into-water" {...props}></Icon>
