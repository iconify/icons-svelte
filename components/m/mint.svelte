<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae8echs6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ae8echs6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mint" {...props}></Icon>
