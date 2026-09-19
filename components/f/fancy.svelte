<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlbwn-y9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":341,"height":512};
const content = `<path class="xlbwn-y9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fancy" {...props}></Icon>
