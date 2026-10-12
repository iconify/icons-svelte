<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f71l33bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f71l33bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-fill-20" {...props}></Icon>
