<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywfwksb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ywfwksb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:clarion" {...props}></Icon>
