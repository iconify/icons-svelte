<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kajv0hbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kajv0hbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:folder-exclamation-16-solid" {...props}></Icon>
