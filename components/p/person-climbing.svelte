<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to8q6wbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="to8q6wbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-climbing" {...props}></Icon>
