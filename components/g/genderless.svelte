<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ellay1bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1280};
const content = `<path class="ellay1bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:genderless" {...props}></Icon>
