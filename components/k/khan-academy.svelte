<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1f4c38_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a1f4c38_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:khan-academy" {...props}></Icon>
