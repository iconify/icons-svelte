<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd20mybht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cd20mybht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-3x3-16-solid" {...props}></Icon>
