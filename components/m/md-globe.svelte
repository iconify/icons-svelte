<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqae7zbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqae7zbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-globe" {...props}></Icon>
