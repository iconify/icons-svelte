<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaj2k9b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iaj2k9b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:microscope" {...props}></Icon>
