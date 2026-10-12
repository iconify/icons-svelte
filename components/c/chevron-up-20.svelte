<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf0z_fbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tf0z_fbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-up-20" {...props}></Icon>
