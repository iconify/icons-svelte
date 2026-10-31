<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdjlbn8gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zdjlbn8gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:check-square-16-solid" {...props}></Icon>
