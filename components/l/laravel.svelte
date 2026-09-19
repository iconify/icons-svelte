<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzc_ihq3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":498,"height":512};
const content = `<path class="bzc_ihq3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:laravel" {...props}></Icon>
