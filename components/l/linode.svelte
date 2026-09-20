<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh-uhxbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eh-uhxbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:linode" {...props}></Icon>
