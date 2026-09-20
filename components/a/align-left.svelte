<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnhyq8uca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tnhyq8uca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:align-left" {...props}></Icon>
