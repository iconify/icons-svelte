<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjgd94-9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pjgd94-9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x3-16-solid" {...props}></Icon>
