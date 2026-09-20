<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfzotcwxd.css';
import '../../css/e/eart31dpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jfzotcwxd"/><path class="eart31dpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:peso" {...props}></Icon>
