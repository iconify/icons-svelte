<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avdw4obvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="avdw4obvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pregnant-person-standing" {...props}></Icon>
