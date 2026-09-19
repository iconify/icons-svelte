<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af5t8lpnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="af5t8lpnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-circle-plus" {...props}></Icon>
