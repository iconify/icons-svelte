<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7nazwb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i7nazwb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:11ty" {...props}></Icon>
