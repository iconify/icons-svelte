<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea1rhccvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ea1rhccvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:envelope-open" {...props}></Icon>
