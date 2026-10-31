<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqdmo49vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cqdmo49vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-bottom-left-on-square-20-solid" {...props}></Icon>
