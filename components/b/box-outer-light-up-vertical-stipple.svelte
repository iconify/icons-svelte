<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujm9vhbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ujm9vhbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-up-vertical-stipple" {...props}></Icon>
