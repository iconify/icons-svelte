<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e41i3kafz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e41i3kafz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:archive-box-arrow-up-16-solid" {...props}></Icon>
