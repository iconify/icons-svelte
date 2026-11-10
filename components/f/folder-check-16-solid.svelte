<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7322fblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b7322fblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-check-16-solid" {...props}></Icon>
