<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuffd7q-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="tuffd7q-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-square-down-right" {...props}></Icon>
