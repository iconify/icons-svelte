<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-0aukb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b-0aukb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mac-option" {...props}></Icon>
