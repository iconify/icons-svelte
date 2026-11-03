<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e71i78b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e71i78b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:leaf-20-solid" {...props}></Icon>
