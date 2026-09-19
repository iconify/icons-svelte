<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f85jvzb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f85jvzb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:laravel" {...props}></Icon>
