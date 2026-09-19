<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqaee4b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqaee4b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic-circle" {...props}></Icon>
