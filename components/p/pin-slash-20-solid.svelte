<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fatbecbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fatbecbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pin-slash-20-solid" {...props}></Icon>
