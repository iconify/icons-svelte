<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5kd1xbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="o5kd1xbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ram" {...props}></Icon>
