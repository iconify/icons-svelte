<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn7h90e6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="sn7h90e6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cloud-download-alt" {...props}></Icon>
