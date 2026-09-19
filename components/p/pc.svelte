<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-jn3bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":690};
const content = `<path class="bp-jn3bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:pc" {...props}></Icon>
