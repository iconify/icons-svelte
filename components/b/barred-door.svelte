<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s35qsybcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s35qsybcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:barred-door" {...props}></Icon>
