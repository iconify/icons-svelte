<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o16_wrbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1024};
const content = `<path class="o16_wrbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:clipboard" {...props}></Icon>
