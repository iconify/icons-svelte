<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj4-zfdlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qj4-zfdlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eye-fill-20" {...props}></Icon>
