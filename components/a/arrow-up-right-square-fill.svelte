<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwzbv5bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mwzbv5bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-right-square-fill" {...props}></Icon>
