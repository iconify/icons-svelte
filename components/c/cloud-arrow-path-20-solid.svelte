<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4vdj2bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j4vdj2bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-arrow-path-20-solid" {...props}></Icon>
