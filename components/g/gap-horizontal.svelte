<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlvz2mwag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlvz2mwag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:gap-horizontal" {...props}></Icon>
