<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqjart1so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fqjart1so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:hammer" {...props}></Icon>
