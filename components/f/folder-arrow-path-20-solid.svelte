<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0-3g3rak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g0-3g3rak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-arrow-path-20-solid" {...props}></Icon>
