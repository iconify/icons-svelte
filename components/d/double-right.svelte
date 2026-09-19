<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9j7mqbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x9j7mqbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:double-right" {...props}></Icon>
