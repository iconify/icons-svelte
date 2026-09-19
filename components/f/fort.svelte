<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufysa6byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ufysa6byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fort" {...props}></Icon>
