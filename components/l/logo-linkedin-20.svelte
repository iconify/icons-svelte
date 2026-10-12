<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ultpy5svx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ultpy5svx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-linkedin-20" {...props}></Icon>
