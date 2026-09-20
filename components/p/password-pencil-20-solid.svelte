<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p---bzhvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p---bzhvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-pencil-20-solid" {...props}></Icon>
