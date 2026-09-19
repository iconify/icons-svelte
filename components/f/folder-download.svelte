<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_ycsvmei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h_ycsvmei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:folder-download" {...props}></Icon>
