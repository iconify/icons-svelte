<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9ytm8b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="o9ytm8b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:filter" {...props}></Icon>
