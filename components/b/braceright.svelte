<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r08ed1f0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":289,"height":960};
const content = `<path class="r08ed1f0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:braceright" {...props}></Icon>
