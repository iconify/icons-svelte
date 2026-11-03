<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn0m4nbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xn0m4nbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:leaf-16-solid" {...props}></Icon>
