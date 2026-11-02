<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax6hn1byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ax6hn1byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-male-16-solid" {...props}></Icon>
