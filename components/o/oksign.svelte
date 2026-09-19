<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smrfk4eck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="smrfk4eck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:oksign" {...props}></Icon>
