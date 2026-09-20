<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8mjr5bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v8mjr5bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud" {...props}></Icon>
