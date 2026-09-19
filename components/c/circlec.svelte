<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7texh2rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r7texh2rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlec" {...props}></Icon>
