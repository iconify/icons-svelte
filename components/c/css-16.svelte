<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndik99b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ndik99b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:css-16" {...props}></Icon>
