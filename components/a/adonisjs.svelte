<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9qskfbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y9qskfbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adonisjs" {...props}></Icon>
