<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjfreibgp.css';
import '../../css/c/ca5ecz53l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rjfreibgp"/><path class="ca5ecz53l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fit-to-width" {...props}></Icon>
