<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk2r7gbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sk2r7gbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:crop-16-solid" {...props}></Icon>
