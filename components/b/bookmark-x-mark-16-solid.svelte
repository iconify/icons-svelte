<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlv1ewbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zlv1ewbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bookmark-x-mark-16-solid" {...props}></Icon>
