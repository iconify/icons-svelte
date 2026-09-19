<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajplf7bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ajplf7bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:reddit" {...props}></Icon>
