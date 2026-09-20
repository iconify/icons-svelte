<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt5c0vb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xt5c0vb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x2-16-solid" {...props}></Icon>
