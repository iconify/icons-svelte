<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac6_keb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ac6_keb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bison" {...props}></Icon>
