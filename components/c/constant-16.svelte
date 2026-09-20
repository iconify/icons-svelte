<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrwjpkbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lrwjpkbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:constant-16" {...props}></Icon>
