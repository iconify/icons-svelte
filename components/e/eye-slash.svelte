<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6apa6btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="n6apa6btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:eye-slash" {...props}></Icon>
