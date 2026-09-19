<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc0zplb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nc0zplb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrows-turn-to-dots" {...props}></Icon>
