<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpoaq1bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="jpoaq1bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:home-11" {...props}></Icon>
