<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmoujxouz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":225,"height":512};
const content = `<path class="vmoujxouz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:gulp" {...props}></Icon>
