<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft4m3528r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ft4m3528r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-sun-bolt" {...props}></Icon>
