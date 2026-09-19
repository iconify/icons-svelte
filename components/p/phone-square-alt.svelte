<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg59v6okj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mg59v6okj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:phone-square-alt" {...props}></Icon>
