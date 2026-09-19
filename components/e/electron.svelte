<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnxad5b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":474,"height":512};
const content = `<path class="jnxad5b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:electron" {...props}></Icon>
