<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxokynb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hxokynb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:airhorn" {...props}></Icon>
