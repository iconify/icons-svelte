<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9_97lbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s9_97lbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:pencil" {...props}></Icon>
