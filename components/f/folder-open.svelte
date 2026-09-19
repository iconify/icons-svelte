<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfv_e4gpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="jfv_e4gpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:folder-open" {...props}></Icon>
