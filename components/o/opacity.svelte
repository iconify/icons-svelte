<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um0rcfaau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="um0rcfaau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:opacity" {...props}></Icon>
