<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdu8ar_ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sdu8ar_ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-upload" {...props}></Icon>
