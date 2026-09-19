<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbrh-8l3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rbrh-8l3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlefork" {...props}></Icon>
