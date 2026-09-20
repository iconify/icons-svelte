<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_7bugblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l_7bugblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:chevron-lg-up" {...props}></Icon>
