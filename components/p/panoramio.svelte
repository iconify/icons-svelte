<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edd6-bgqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="edd6-bgqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:panoramio" {...props}></Icon>
