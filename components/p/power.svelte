<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viie0hb-o.css';
import '../../css/f/fiyd37bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="viie0hb-o"/><path class="fiyd37bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:power" {...props}></Icon>
