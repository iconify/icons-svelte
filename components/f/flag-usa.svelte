<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4zlantmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="v4zlantmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:flag-usa" {...props}></Icon>
