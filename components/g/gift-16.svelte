<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evhrrmisg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="evhrrmisg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gift-16" {...props}></Icon>
