<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gykvj3bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gykvj3bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:fork-knife-16-solid" {...props}></Icon>
