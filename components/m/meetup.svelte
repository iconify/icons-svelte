<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlx_r6b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zlx_r6b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:meetup" {...props}></Icon>
